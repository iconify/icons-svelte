<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yi-d3bcqw.css';
import '../../css/t/t0gc7texs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yi-d3bcqw"/><path class="t0gc7texs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rabbit-20-bold" {...props}></Icon>
