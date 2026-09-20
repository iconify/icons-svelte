<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yu8_hgk1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yu8_hgk1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:look-down-fill" {...props}></Icon>
