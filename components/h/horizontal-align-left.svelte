<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e03d1ubcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e03d1ubcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:horizontal-align-left" {...props}></Icon>
