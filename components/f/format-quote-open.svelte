<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xpnnjfyzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xpnnjfyzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:format-quote-open" {...props}></Icon>
