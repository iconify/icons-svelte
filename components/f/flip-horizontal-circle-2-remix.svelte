<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvg0zneje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fvg0zneje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:flip-horizontal-circle-2-remix" {...props}></Icon>
