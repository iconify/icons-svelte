<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbwinxbqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mbwinxbqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:hat-wizard" {...props}></Icon>
