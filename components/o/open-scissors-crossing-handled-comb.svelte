<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ttle3lbib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ttle3lbib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:open-scissors-crossing-handled-comb" {...props}></Icon>
