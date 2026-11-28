<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1gdfy-3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y1gdfy-3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:folder-sparkles-solid" {...props}></Icon>
