<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvxo4mbnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zvxo4mbnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:citibank-light" {...props}></Icon>
