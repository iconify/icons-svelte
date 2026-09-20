<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qp057s9bi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qp057s9bi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:flower-line" {...props}></Icon>
