<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ci23lkb2t.css';
import '../../css/q/qfc3cc3so.css';
import '../../css/z/zvg42bbsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="ci23lkb2t"/><path class="qfc3cc3so"/><path class="zvg42bbsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:angola" {...props}></Icon>
