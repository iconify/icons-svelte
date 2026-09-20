<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fi7cakbdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="fi7cakbdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:bath" {...props}></Icon>
