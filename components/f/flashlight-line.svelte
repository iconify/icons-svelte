<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/outjcqzju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="outjcqzju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:flashlight-line" {...props}></Icon>
