<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpr1c-b9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="mpr1c-b9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:folder-globe" {...props}></Icon>
