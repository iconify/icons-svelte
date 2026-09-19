<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qr86_qu0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qr86_qu0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:add-outline" {...props}></Icon>
