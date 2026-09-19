<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ykltvrbat.css';
import '../../css/l/l6dxx07jx.css';
import '../../css/f/f9qpihbxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ykltvrbat"/><path class="l6dxx07jx"/><path class="f9qpihbxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:lastquartermoonface" {...props}></Icon>
