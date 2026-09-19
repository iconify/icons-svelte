<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1wv3xwuv.css';
import '../../css/u/u2y96rwvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="d1wv3xwuv"/><path class="u2y96rwvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:insert-syntax" {...props}></Icon>
