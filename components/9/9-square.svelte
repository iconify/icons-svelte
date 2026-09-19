<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwhr9xfgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="bwhr9xfgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:9-square" {...props}></Icon>
