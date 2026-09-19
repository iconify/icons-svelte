<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5_ov5lgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="c5_ov5lgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:paint-bucket" {...props}></Icon>
