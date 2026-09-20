<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4m5ykbxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t4m5ykbxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:donate-off" {...props}></Icon>
