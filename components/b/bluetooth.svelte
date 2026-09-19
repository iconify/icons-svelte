<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5619jkwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="a5619jkwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:bluetooth" {...props}></Icon>
