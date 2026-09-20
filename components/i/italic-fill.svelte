<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xkc6rkbhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xkc6rkbhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:italic-fill" {...props}></Icon>
