<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6ku53bvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="n6ku53bvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:charging-station" {...props}></Icon>
