<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8uv-mb7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="z8uv-mb7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:frequency-48" {...props}></Icon>
