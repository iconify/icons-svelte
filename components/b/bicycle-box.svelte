<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxluiabmz.css';
import '../../css/t/tsf60-bka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="sxluiabmz"/><path class="tsf60-bka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:bicycle-box" {...props}></Icon>
