<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c625b_u-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c625b_u-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:pay-money" {...props}></Icon>
