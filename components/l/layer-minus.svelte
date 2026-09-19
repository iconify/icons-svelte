<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ty4zwew1b.css';
import '../../css/s/sar0t8bmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ty4zwew1b"/><path class="sar0t8bmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:layer-minus" {...props}></Icon>
