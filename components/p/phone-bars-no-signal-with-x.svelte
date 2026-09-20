<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdnblzblg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pdnblzblg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:phone-bars-no-signal-with-x" {...props}></Icon>
