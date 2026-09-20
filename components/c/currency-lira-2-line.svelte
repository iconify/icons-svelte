<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iomt7boyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iomt7boyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:currency-lira-2-line" {...props}></Icon>
