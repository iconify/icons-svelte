<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdeiz2vni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="pdeiz2vni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:g-outline" {...props}></Icon>
