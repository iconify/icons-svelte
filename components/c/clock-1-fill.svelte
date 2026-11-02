<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/krrk9_xhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="krrk9_xhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:clock-1-fill" {...props}></Icon>
