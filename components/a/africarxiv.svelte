<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fy4evacsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="fy4evacsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:africarxiv" {...props}></Icon>
