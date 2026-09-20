<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bl_aeqqyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bl_aeqqyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-align-right" {...props}></Icon>
