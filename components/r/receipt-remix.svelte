<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/if1i_5bwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="if1i_5bwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:receipt-remix" {...props}></Icon>
