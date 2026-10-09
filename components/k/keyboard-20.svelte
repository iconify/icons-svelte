<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5p77gmzy.css';
import '../../css/x/xetxy-b7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="z5p77gmzy"/><path class="xetxy-b7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:keyboard-20" {...props}></Icon>
