<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jeyutuz7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jeyutuz7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:adminerevo-light" {...props}></Icon>
