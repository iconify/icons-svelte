<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qx071qbax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="qx071qbax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:cake-candles" {...props}></Icon>
