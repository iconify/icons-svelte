<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_oe4usja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l_oe4usja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:close-medium-fill" {...props}></Icon>
