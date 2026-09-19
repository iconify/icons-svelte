<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p19pb4brm.css';
import '../../css/b/bm_a0o4dd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="p19pb4brm"/><path class="bm_a0o4dd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:kissmark" {...props}></Icon>
