<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cx15z85sq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="cx15z85sq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:qwen-wordmark" {...props}></Icon>
