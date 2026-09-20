<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbpey7bru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="cbpey7bru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:flag" {...props}></Icon>
