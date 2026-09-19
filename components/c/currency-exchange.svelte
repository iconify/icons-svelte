<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pll1c7hqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pll1c7hqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:currency-exchange" {...props}></Icon>
