<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0pmbdb-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0pmbdb-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chart-column-decreasing-line" {...props}></Icon>
