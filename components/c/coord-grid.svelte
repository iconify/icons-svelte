<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g57i3fc6z.css';
import '../../css/e/eedc6fbmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="g57i3fc6z"/><path class="eedc6fbmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:coord-grid" {...props}></Icon>
