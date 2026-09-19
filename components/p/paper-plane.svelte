<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9y6t444d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="n9y6t444d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:paper-plane" {...props}></Icon>
