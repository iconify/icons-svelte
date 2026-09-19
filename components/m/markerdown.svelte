<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wx4kzbcrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1024};
const content = `<path class="wx4kzbcrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:markerdown" {...props}></Icon>
