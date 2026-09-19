<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2hgrbbwz.css';
import '../../css/c/cnr4z9ptg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="r2hgrbbwz"/><path class="cnr4z9ptg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:guide-dog" {...props}></Icon>
