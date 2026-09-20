<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1nyptb_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x1nyptb_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:checkup-chart-bold" {...props}></Icon>
