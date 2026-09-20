<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cw52gbqmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cw52gbqmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:phone-bars-weakest-signal" {...props}></Icon>
