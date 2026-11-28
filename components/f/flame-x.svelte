<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_15s1bpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x_15s1bpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:flame-x" {...props}></Icon>
