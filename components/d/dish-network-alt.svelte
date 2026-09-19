<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhmh6qbmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nhmh6qbmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:dish-network-alt" {...props}></Icon>
