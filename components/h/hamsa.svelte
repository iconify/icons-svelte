<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7es-7bvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v7es-7bvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:hamsa" {...props}></Icon>
