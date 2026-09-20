<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pl6x-yv6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="pl6x-yv6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:markdown" {...props}></Icon>
