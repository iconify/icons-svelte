<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/by2od_5uy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="by2od_5uy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:4chan" {...props}></Icon>
