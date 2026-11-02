<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xq3v-ebal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xq3v-ebal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:moon-sleep-fill" {...props}></Icon>
