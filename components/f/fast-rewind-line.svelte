<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtmxdq75g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jtmxdq75g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fast-rewind-line" {...props}></Icon>
