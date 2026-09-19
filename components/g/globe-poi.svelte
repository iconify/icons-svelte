<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cj_8lcczn.css';
import '../../css/x/xy4c9hbng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="cj_8lcczn"/><path class="xy4c9hbng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:globe-poi" {...props}></Icon>
