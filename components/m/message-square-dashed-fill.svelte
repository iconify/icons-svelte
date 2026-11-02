<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9hkbstkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p9hkbstkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:message-square-dashed-fill" {...props}></Icon>
