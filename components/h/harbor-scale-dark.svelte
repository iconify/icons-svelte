<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ooo7ryxbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ooo7ryxbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:harbor-scale-dark" {...props}></Icon>
