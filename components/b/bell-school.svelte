<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vkgnl-x2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vkgnl-x2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:bell-school" {...props}></Icon>
