<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkt06ackd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pkt06ackd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-big-up-solid" {...props}></Icon>
