<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wa3dtqdna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wa3dtqdna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:beaker" {...props}></Icon>
