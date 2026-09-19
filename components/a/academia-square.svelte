<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygl6n1i5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="ygl6n1i5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:academia-square" {...props}></Icon>
