<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mo51s6uhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mo51s6uhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:box-minus" {...props}></Icon>
