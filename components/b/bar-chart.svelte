<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tc5e8lyyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tc5e8lyyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:bar-chart" {...props}></Icon>
