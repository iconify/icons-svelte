<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zyhm07bjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zyhm07bjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:4-plus" {...props}></Icon>
