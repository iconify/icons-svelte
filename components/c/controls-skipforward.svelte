<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkg6rsqjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wkg6rsqjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:controls-skipforward" {...props}></Icon>
