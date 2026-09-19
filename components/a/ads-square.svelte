<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgyj5egpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="wgyj5egpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:ads-square" {...props}></Icon>
