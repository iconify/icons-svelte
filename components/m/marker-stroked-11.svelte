<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m63vg2bps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="m63vg2bps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:marker-stroked-11" {...props}></Icon>
