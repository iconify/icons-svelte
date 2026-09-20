<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szplzeb1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="szplzeb1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:champagne-party-alcohol-remix" {...props}></Icon>
