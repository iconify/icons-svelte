<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q90_u7bjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="q90_u7bjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:copy-poly" {...props}></Icon>
