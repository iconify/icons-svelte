<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thdmt63vd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="thdmt63vd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:aspect-ratio" {...props}></Icon>
