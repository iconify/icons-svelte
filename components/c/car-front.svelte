<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tl7c8kphf.css';
import '../../css/j/ja_pkqero.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tl7c8kphf"/><path class="ja_pkqero"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:car-front" {...props}></Icon>
