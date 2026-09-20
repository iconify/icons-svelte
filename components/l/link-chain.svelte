<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/np1cm194g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="np1cm194g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:link-chain" {...props}></Icon>
