<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbmj_suox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qbmj_suox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bookmark-check-fill" {...props}></Icon>
