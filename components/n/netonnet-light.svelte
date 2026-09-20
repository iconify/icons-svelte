<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7pdt9bzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n7pdt9bzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:netonnet-light" {...props}></Icon>
