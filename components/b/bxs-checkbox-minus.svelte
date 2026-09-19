<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjk-i_bpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yjk-i_bpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-checkbox-minus" {...props}></Icon>
