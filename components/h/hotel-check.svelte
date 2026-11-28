<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r93x0obzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r93x0obzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:hotel-check" {...props}></Icon>
