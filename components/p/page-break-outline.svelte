<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhqd6abgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="vhqd6abgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:page-break-outline" {...props}></Icon>
