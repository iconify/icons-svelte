<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rill5m66m.css';
import '../../css/e/ei2u0fbjq.css';
import '../../css/h/hf9qlabiz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rill5m66m"/><path class="ei2u0fbjq"/><path class="hf9qlabiz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:drawing-compass-20-bold" {...props}></Icon>
