<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ey4o1_bee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ey4o1_bee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bank-minus" {...props}></Icon>
