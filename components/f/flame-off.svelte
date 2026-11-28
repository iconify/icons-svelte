<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/miyh6-9ir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="miyh6-9ir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:flame-off" {...props}></Icon>
