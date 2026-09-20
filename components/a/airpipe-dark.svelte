<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chhzk1bmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="chhzk1bmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:airpipe-dark" {...props}></Icon>
