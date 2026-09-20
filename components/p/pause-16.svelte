<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zntwc7g4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zntwc7g4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:pause-16" {...props}></Icon>
