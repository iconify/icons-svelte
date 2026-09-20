<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ph9nw1sum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ph9nw1sum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:filter" {...props}></Icon>
