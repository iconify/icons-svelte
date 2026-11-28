<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7k7dxbpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q7k7dxbpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:map-pin-minus" {...props}></Icon>
