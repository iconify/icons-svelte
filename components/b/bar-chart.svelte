<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5u4lfsns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y5u4lfsns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:bar-chart" {...props}></Icon>
