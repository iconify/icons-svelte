<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvu_tubrj.css';
import '../../css/y/yb873zwsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fvu_tubrj"/><path clip-rule="evenodd" class="yb873zwsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:content-add-folder" {...props}></Icon>
