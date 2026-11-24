<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gotpsbcpu.css';
import '../../css/w/wxtz8objy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gotpsbcpu"/><path class="wxtz8objy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:flashlight-off-filled" {...props}></Icon>
