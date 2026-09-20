<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/un82f_hcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="un82f_hcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:notification-line" {...props}></Icon>
