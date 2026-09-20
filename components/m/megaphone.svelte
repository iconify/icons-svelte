<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6of4gbjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="z6of4gbjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:megaphone" {...props}></Icon>
