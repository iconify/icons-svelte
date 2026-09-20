<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wx6cf-bmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="wx6cf-bmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:puzzle-piece" {...props}></Icon>
