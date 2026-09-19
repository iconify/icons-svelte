<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_uu_bb8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="g_uu_bb8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:layer-add" {...props}></Icon>
