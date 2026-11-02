<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wutb45b_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wutb45b_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:globe-x-fill" {...props}></Icon>
