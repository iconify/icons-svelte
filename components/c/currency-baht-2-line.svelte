<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjya9dbzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xjya9dbzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:currency-baht-2-line" {...props}></Icon>
