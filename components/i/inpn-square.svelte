<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6thpwbnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="y6thpwbnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:inpn-square" {...props}></Icon>
