<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytc-hrbpf.css';
import '../../css/x/xtnb74b1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ytc-hrbpf"/><path class="xtnb74b1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:noodle-bowl" {...props}></Icon>
