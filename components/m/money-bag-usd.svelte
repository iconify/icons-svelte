<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uax-zvfsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="uax-zvfsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:money-bag-usd" {...props}></Icon>
