<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5z1758ht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="z5z1758ht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:original-size-fill-12" {...props}></Icon>
