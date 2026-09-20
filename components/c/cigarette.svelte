<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipgay6bzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ipgay6bzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:cigarette" {...props}></Icon>
