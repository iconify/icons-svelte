<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhbr0d30n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dhbr0d30n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bowling-pin-and-bowling-ball" {...props}></Icon>
