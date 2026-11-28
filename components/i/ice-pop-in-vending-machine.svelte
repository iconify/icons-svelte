<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6opc0buw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="n6opc0buw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:ice-pop-in-vending-machine" {...props}></Icon>
