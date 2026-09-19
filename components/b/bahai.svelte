<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tlbiui_0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tlbiui_0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bahai" {...props}></Icon>
