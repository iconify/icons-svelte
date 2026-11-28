<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p28jsbc8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="p28jsbc8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:restroom" {...props}></Icon>
