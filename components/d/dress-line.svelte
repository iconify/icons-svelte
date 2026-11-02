<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkfa4fbeh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wkfa4fbeh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:dress-line" {...props}></Icon>
