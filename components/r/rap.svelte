<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kr1oj39_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kr1oj39_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:rap" {...props}></Icon>
