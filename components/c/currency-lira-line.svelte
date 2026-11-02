<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shu7_ybxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="shu7_ybxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:currency-lira-line" {...props}></Icon>
