<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sc1grwbju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sc1grwbju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:fuel-check" {...props}></Icon>
