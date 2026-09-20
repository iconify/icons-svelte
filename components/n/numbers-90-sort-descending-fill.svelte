<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itluvfbsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="itluvfbsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:numbers-90-sort-descending-fill" {...props}></Icon>
