<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzcyxtyei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jzcyxtyei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cursor-crosshair-dot-filled" {...props}></Icon>
