<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wudh0hbyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="wudh0hbyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:doughnutchart-filled" {...props}></Icon>
