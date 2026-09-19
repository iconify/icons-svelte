<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzwc1y54b.css';
import '../../css/r/ra66rbckd.css';
import '../../css/z/zgszk2b4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bzwc1y54b"/><path class="ra66rbckd"/><path class="zgszk2b4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:play-outline-filled" {...props}></Icon>
