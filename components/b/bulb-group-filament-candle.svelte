<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pk6r-mbyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pk6r-mbyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:bulb-group-filament-candle" {...props}></Icon>
