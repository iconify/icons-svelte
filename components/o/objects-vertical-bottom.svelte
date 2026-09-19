<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2u2kvb1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r2u2kvb1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:objects-vertical-bottom" {...props}></Icon>
