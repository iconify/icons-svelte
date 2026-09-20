<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5j900bsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c5j900bsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:bug" {...props}></Icon>
