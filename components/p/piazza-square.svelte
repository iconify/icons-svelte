<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-_4ewbhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="k-_4ewbhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:piazza-square" {...props}></Icon>
