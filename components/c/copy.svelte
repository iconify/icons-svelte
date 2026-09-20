<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebesbc4wt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ebesbc4wt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:copy" {...props}></Icon>
