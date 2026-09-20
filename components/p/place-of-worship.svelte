<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ogg4ex6bi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="ogg4ex6bi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:place-of-worship" {...props}></Icon>
