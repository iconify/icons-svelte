<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/juwqysb1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="juwqysb1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:bar-chart-line" {...props}></Icon>
