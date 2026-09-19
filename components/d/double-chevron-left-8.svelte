<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzl2byfkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="pzl2byfkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:double-chevron-left-8" {...props}></Icon>
