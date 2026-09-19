<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t44iphbtl.css';
import '../../css/x/xq-7rxmzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="t44iphbtl"/><path class="xq-7rxmzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:box" {...props}></Icon>
