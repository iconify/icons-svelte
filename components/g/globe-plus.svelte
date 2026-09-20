<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gw8u1vbft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gw8u1vbft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:globe-plus" {...props}></Icon>
