<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pow4apbxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1025};
const content = `<path class="pow4apbxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:racquet" {...props}></Icon>
