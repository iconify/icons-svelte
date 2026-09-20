<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/azae8fb_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="azae8fb_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:external-link" {...props}></Icon>
