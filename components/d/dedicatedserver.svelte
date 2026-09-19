<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pk422ub4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="pk422ub4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:dedicatedserver" {...props}></Icon>
