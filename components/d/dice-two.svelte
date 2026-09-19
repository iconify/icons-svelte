<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vb6y-xcsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="vb6y-xcsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:dice-two" {...props}></Icon>
