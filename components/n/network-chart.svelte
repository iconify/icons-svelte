<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhxa97bjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uhxa97bjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:network-chart" {...props}></Icon>
