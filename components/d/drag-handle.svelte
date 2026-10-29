<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rsbk96brv.css';
import '../../css/o/odpdy0bir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rsbk96brv"/><path class="odpdy0bir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:drag-handle" {...props}></Icon>
