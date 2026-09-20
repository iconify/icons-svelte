<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-j5vklnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u-j5vklnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:high-voltage-power-line" {...props}></Icon>
