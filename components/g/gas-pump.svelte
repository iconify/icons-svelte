<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fiz9pibyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fiz9pibyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:gas-pump" {...props}></Icon>
