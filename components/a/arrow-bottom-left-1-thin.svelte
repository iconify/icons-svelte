<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spx7v0bsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="spx7v0bsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-bottom-left-1-thin" {...props}></Icon>
