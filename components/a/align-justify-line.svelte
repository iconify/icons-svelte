<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njne1h_oo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="njne1h_oo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:align-justify-line" {...props}></Icon>
