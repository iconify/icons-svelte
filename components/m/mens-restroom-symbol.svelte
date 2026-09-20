<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kliljjg0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kliljjg0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:mens-restroom-symbol" {...props}></Icon>
