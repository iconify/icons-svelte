<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w32e8gb_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1728,"height":1536};
const content = `<path class="w32e8gb_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:flag-o" {...props}></Icon>
