<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvsinl_3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1025};
const content = `<path class="dvsinl_3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:moneyalt" {...props}></Icon>
