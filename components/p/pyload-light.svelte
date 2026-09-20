<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqfiwcbwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cqfiwcbwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pyload-light" {...props}></Icon>
