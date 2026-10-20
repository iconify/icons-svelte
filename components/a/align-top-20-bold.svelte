<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_320w4ee.css';
import '../../css/e/ec0kd2kjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="u_320w4ee"/><path class="ec0kd2kjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:align-top-20-bold" {...props}></Icon>
