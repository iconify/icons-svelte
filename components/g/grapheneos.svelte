<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dpt1axmyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dpt1axmyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:grapheneos" {...props}></Icon>
