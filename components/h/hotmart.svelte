<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0-v6c_3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":27,"height":37};
const content = `<path class="m0-v6c_3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:hotmart" {...props}></Icon>
