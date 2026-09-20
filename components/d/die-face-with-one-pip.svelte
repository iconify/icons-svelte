<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulry8uluz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ulry8uluz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:die-face-with-one-pip" {...props}></Icon>
