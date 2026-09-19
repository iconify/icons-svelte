<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x74-3dfpl.css';
import '../../css/i/ioq293cxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="x74-3dfpl"/><path class="ioq293cxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:map-add" {...props}></Icon>
