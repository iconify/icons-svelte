<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e4_y_tr5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="e4_y_tr5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:folder-poi" {...props}></Icon>
