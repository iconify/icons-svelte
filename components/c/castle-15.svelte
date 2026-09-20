<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xy3x42bge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xy3x42bge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:castle-15" {...props}></Icon>
