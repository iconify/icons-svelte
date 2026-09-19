<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sq3q3bfsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="sq3q3bfsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:calculator-not-equal-to" {...props}></Icon>
