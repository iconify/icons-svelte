<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yz8ajv6sy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yz8ajv6sy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:car-light-alert" {...props}></Icon>
