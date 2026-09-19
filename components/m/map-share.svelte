<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7ts5db7w.css';
import '../../css/g/gu3211y0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="w7ts5db7w"/><path class="gu3211y0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:map-share" {...props}></Icon>
