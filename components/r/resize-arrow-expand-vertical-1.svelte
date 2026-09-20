<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-1elsbgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z-1elsbgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:resize-arrow-expand-vertical-1" {...props}></Icon>
