<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgh170btc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="rgh170btc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:antenna" {...props}></Icon>
