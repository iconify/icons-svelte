<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1hhj8bfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n1hhj8bfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:line-chart-octagon-solid" {...props}></Icon>
