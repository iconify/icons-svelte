<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vk8gf1b0k.css';
import '../../css/x/xtkl7sp6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vk8gf1b0k"/><path class="xtkl7sp6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:exposure" {...props}></Icon>
