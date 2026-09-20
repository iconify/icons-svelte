<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frv0s0blb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="frv0s0blb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:pumpkin" {...props}></Icon>
