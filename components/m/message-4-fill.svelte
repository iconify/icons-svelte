<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbxx-hb_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mbxx-hb_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:message-4-fill" {...props}></Icon>
