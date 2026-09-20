<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxprrt3ft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":25};
const content = `<path clip-rule="evenodd" class="qxprrt3ft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:funnel-1" {...props}></Icon>
