<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgy9fjbif.css';
import '../../css/f/fvtvtsbqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jgy9fjbif"/><path class="fvtvtsbqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:content-file" {...props}></Icon>
