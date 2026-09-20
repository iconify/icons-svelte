<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lb9f9lq0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="lb9f9lq0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:plumber" {...props}></Icon>
