<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h30_pj2ow.css';
import '../../css/t/tmh0ewb2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h30_pj2ow"/><path class="tmh0ewb2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:dock-right-alt" {...props}></Icon>
