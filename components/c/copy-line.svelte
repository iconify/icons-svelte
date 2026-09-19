<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/huoyumh1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="huoyumh1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:copy-line" {...props}></Icon>
