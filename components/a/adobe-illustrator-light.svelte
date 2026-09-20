<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czqq3livj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="czqq3livj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:adobe-illustrator-light" {...props}></Icon>
