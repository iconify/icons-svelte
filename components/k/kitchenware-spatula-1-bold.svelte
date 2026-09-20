<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7v3kjbav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r7v3kjbav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:kitchenware-spatula-1-bold" {...props}></Icon>
