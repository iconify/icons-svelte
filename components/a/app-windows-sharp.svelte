<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o91b5sbba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o91b5sbba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:app-windows-sharp" {...props}></Icon>
