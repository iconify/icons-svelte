<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omhm-gykt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="omhm-gykt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:palace-2-fill" {...props}></Icon>
