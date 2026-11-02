<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xtjmx2rke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xtjmx2rke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:lipstick-fill" {...props}></Icon>
