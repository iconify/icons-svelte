<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tdn5rpciy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tdn5rpciy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:display-line" {...props}></Icon>
