<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/is_oe-rmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="is_oe-rmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:lancache-net-dark" {...props}></Icon>
