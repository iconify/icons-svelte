<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9fsllkmh.css';
import '../../css/o/ocy9tacha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c9fsllkmh"/><path class="ocy9tacha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:monopole-pylon-20-bold" {...props}></Icon>
