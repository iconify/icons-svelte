<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4ro4s-2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="g4ro4s-2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:cup-with-steam-in-vending-machine" {...props}></Icon>
