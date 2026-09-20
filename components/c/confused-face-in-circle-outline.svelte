<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uelx27b-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="uelx27b-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:confused-face-in-circle-outline" {...props}></Icon>
