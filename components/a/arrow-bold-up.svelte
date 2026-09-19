<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6u6u_bcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f6u6u_bcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:arrow-bold-up" {...props}></Icon>
