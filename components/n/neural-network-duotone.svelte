<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1y8uidcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g1y8uidcj primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:neural-network-duotone" {...props}></Icon>
