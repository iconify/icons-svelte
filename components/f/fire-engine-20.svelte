<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/um9jo7bca.css';
import '../../css/r/r5ivvvbes.css';
import '../../css/r/r7w_ozowo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="um9jo7bca"/><path class="r5ivvvbes"/><path class="r7w_ozowo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fire-engine-20" {...props}></Icon>
