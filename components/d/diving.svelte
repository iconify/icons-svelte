<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trz6_5eei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="trz6_5eei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:diving" {...props}></Icon>
