<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eeidxnbcj.css';
import '../../css/l/loxl4zb4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eeidxnbcj"/><path class="loxl4zb4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:ranking-bold" {...props}></Icon>
