<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx24dwzoq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jx24dwzoq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:calculator-variant-outline" {...props}></Icon>
