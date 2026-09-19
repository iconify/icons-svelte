<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qeq1y5_1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qeq1y5_1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:grab" {...props}></Icon>
