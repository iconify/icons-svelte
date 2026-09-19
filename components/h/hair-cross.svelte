<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewio2v6iy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ewio2v6iy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:hair-cross" {...props}></Icon>
