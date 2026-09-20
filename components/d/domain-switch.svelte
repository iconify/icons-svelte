<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6-5yob4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s6-5yob4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:domain-switch" {...props}></Icon>
