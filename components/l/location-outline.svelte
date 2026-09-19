<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/risuy3bam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="risuy3bam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:location-outline" {...props}></Icon>
