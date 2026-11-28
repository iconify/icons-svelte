<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9jyzr26n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u9jyzr26n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:receipt-x" {...props}></Icon>
