<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k85tt3ajc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":384};
const content = `<path class="k85tt3ajc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:looks" {...props}></Icon>
