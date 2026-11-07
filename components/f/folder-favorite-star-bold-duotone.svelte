<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2nrf10bf.css';
import '../../css/n/nxk8rccaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q2nrf10bf"/><path class="nxk8rccaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-favorite-star-bold-duotone" {...props}></Icon>
