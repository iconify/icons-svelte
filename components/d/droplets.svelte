<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddvgu8bvv.css';
import '../../css/o/ogt7h3bjy.css';
import '../../css/e/eu2jph4ne.css';
import '../../css/y/ys0g5f80g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ddvgu8bvv"><path class="ogt7h3bjy"/><path class="eu2jph4ne"/><path class="ys0g5f80g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:droplets" {...props}></Icon>
