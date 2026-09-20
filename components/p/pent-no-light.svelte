<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5t102bbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y5t102bbt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pent-no-light" {...props}></Icon>
