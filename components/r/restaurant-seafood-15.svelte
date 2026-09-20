<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipb0gbcjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ipb0gbcjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:restaurant-seafood-15" {...props}></Icon>
