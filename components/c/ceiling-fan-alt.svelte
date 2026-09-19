<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sspix23by.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sspix23by"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ceiling-fan-alt" {...props}></Icon>
