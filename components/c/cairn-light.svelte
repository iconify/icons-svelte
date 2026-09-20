<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q60h5cboi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q60h5cboi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cairn-light" {...props}></Icon>
