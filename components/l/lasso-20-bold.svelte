<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egr9hrb-r.css';
import '../../css/z/zhxx2z6mr.css';
import '../../css/i/iw63emb2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="egr9hrb-r"/><path class="zhxx2z6mr"/><path class="iw63emb2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:lasso-20-bold" {...props}></Icon>
