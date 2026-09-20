<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jg778vblv.css';
import '../../css/p/pbnebbk0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jg778vblv"/><path clip-rule="evenodd" class="pbnebbk0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:money-credit-card" {...props}></Icon>
