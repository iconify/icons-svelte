<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ayo-8cbjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ayo-8cbjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:laughing-face-in-circle-outline" {...props}></Icon>
