<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ng7wvzb7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ng7wvzb7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:loading-2" {...props}></Icon>
