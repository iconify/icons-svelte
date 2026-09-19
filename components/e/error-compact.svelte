<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qkdog0g-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="qkdog0g-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:error-compact" {...props}></Icon>
