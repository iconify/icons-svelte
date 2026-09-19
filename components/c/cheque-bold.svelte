<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cr1y6128i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cr1y6128i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:cheque-bold" {...props}></Icon>
