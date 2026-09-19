<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgk3i7bfw.css';
import '../../css/g/g5jh10vug.css';
import '../../css/k/ko92zebxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sgk3i7bfw"/><path class="g5jh10vug"/><path class="ko92zebxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ear-outline" {...props}></Icon>
