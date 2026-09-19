<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fsy6j0bhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="fsy6j0bhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:hourglass-empty" {...props}></Icon>
