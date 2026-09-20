<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjjdcsb8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="fjjdcsb8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:expand" {...props}></Icon>
