<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a6m9uabxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="a6m9uabxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:raised-curb-with-exclamation-point" {...props}></Icon>
