<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxe8bc6ej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dxe8bc6ej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:file-check-round" {...props}></Icon>
