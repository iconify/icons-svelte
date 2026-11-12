<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxnlo4bej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jxnlo4bej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hanko-dark" {...props}></Icon>
