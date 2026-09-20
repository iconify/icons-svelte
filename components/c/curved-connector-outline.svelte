<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvpuq0rfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="vvpuq0rfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:curved-connector-outline" {...props}></Icon>
