<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0fsgfb1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s0fsgfb1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:chart-table" {...props}></Icon>
