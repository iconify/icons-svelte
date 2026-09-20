<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fzehumb2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fzehumb2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:panorama-wide-angle" {...props}></Icon>
