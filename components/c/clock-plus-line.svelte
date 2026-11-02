<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_b3mzfrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i_b3mzfrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:clock-plus-line" {...props}></Icon>
