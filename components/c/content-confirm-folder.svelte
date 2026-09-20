<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvu_tubrj.css';
import '../../css/w/wz_m09d-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fvu_tubrj"/><path clip-rule="evenodd" class="wz_m09d-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:content-confirm-folder" {...props}></Icon>
