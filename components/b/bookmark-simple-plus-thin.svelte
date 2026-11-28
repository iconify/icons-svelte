<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nj8oc32ch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="nj8oc32ch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:bookmark-simple-plus-thin" {...props}></Icon>
