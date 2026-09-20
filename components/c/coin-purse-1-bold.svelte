<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghj6zeexj.css';
import '../../css/i/i1rnhy3qh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ghj6zeexj"/><path class="i1rnhy3qh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:coin-purse-1-bold" {...props}></Icon>
