<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iiv2ygbwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iiv2ygbwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:badge-turkish-lira-line" {...props}></Icon>
