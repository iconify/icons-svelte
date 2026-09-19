<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9b_kub7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="p9b_kub7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:folder-pois" {...props}></Icon>
