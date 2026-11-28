<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-iqofk3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k-iqofk3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:bar-chart-horizontal" {...props}></Icon>
