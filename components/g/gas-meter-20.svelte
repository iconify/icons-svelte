<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jyhbxz_1c.css';
import '../../css/u/u6fgoyb9s.css';
import '../../css/z/zh-hxsbiu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jyhbxz_1c"/><path class="u6fgoyb9s"/><path class="zh-hxsbiu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gas-meter-20" {...props}></Icon>
