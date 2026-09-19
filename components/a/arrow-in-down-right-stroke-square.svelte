<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/opmr5m07o.css';
import '../../css/g/gxsk1y4aw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="opmr5m07o"/><path class="gxsk1y4aw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-in-down-right-stroke-square" {...props}></Icon>
