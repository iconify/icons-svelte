<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ub6fx6bwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ub6fx6bwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:openziti-dark" {...props}></Icon>
