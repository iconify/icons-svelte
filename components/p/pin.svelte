<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1w1dmwgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="l1w1dmwgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pin" {...props}></Icon>
