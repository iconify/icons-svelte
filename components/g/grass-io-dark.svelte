<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xy68ylbgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xy68ylbgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:grass-io-dark" {...props}></Icon>
