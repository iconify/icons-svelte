<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0oqi0odq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="n0oqi0odq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:lighthouse-jp" {...props}></Icon>
