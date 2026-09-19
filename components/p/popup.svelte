<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgwpg6btu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1091,"height":1000};
const content = `<path class="qgwpg6btu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:popup" {...props}></Icon>
