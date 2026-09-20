<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yigswlbps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yigswlbps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:home-2-fill" {...props}></Icon>
