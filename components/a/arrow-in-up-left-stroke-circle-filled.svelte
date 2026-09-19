<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxbgy5bzx.css';
import '../../css/l/l_-go266m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nxbgy5bzx"/><path class="l_-go266m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-in-up-left-stroke-circle-filled" {...props}></Icon>
