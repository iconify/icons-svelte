<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qox-itb7z.css';
import '../../css/y/yh9fei7of.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qox-itb7z"/><path class="yh9fei7of"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:binder-20-bold" {...props}></Icon>
