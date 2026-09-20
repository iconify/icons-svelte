<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5mssp-sb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="y5mssp-sb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bicycle-in-rectangle-outline" {...props}></Icon>
