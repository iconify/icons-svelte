<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c22bshnsy.css';
import '../../css/j/j0hahwblx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="c22bshnsy"/><path class="j0hahwblx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:money-payments-accounting-calculator" {...props}></Icon>
