<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5f5ksbis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="p5f5ksbis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:pixelwand" {...props}></Icon>
