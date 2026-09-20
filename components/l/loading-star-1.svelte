<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7ekl4b5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p7ekl4b5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:loading-star-1" {...props}></Icon>
