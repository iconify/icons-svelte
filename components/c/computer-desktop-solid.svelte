<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vps4jmb0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vps4jmb0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:computer-desktop-solid" {...props}></Icon>
