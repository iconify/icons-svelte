<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6clfonvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q6clfonvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bluetooth-searching-fill" {...props}></Icon>
