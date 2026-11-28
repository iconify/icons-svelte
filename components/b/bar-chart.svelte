<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qy-7kibrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qy-7kibrw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:bar-chart" {...props}></Icon>
