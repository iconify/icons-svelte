<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2jxpbinp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n2jxpbinp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:color-picker-fill" {...props}></Icon>
