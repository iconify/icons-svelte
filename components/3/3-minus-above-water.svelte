<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a6dku23de.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="a6dku23de"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:3-minus-above-water" {...props}></Icon>
