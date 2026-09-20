<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgi_vyerr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mgi_vyerr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:hand-reading" {...props}></Icon>
