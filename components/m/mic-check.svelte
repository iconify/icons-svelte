<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtrxnzxwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rtrxnzxwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:mic-check" {...props}></Icon>
