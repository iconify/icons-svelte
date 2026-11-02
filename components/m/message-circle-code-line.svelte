<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eaav9wpwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eaav9wpwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:message-circle-code-line" {...props}></Icon>
