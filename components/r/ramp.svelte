<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nr9y_5b1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":69.5,"height":59};
const content = `<path class="nr9y_5b1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:ramp" {...props}></Icon>
