<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rx_llqbvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rx_llqbvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:quote-right-fill" {...props}></Icon>
