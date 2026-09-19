<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gv47u9sdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="gv47u9sdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:full-screen" {...props}></Icon>
