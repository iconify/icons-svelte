<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxwtxj0mq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nxwtxj0mq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:pin-drop" {...props}></Icon>
