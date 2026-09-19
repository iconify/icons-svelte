<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xi2jq6bjc.css';
import '../../css/m/mz86u9bpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xi2jq6bjc"/><path class="mz86u9bpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-product-hunt" {...props}></Icon>
