<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2nrf10bf.css';
import '../../css/z/zcmd8xbkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q2nrf10bf"/><path clip-rule="evenodd" class="zcmd8xbkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-clock-bold-duotone" {...props}></Icon>
