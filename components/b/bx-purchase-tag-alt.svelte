<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrxw13bgw.css';
import '../../css/c/c6a7psbpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rrxw13bgw"/><circle class="c6a7psbpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-purchase-tag-alt" {...props}></Icon>
