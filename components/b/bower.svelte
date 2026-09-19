<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wofw3ubgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wofw3ubgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:bower" {...props}></Icon>
