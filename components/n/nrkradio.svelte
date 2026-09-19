<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwd6vqffv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fwd6vqffv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:nrkradio" {...props}></Icon>
