<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixxe14s0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ixxe14s0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:currency-ruble-2-line" {...props}></Icon>
