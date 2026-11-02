<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xj_ymgb-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xj_ymgb-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:circle-arrow-out-down-left-line" {...props}></Icon>
