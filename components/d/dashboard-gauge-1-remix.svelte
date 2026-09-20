<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvj0xrezm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="yvj0xrezm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:dashboard-gauge-1-remix" {...props}></Icon>
