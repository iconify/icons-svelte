<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwps6ee2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rwps6ee2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:pay-code-two" {...props}></Icon>
