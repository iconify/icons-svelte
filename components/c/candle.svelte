<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9q4fnbbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="a9q4fnbbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:candle" {...props}></Icon>
