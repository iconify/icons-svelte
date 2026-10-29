<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7z2amgvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d7z2amgvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:drag-handle" {...props}></Icon>
