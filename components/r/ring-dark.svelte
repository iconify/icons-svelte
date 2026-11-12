<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-758iasb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g-758iasb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ring-dark" {...props}></Icon>
