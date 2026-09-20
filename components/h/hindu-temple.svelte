<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ze6ucbb7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="ze6ucbb7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:hindu-temple" {...props}></Icon>
