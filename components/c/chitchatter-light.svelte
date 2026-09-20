<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqgm24bom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uqgm24bom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:chitchatter-light" {...props}></Icon>
