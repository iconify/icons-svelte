<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rq82k4bla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="rq82k4bla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:hand-back-fist" {...props}></Icon>
