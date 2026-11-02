<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/roib-2ula.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="roib-2ula"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:message-circle-plus-line" {...props}></Icon>
