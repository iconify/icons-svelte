<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/azix1pzje.css';
import '../../css/j/jdmv1bb_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="azix1pzje"/><path class="jdmv1bb_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pen-20" {...props}></Icon>
