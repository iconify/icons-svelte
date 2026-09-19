<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czbq_4byq.css';
import '../../css/w/wq7voubuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="czbq_4byq"/><path class="wq7voubuy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:dress" {...props}></Icon>
