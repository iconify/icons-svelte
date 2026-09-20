<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8-tj_sev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m8-tj_sev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:measuring-tape" {...props}></Icon>
