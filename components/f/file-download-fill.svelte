<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtkl9p4jv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vtkl9p4jv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-download-fill" {...props}></Icon>
