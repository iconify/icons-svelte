<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v216tbc8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="v216tbc8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:first-order-alt" {...props}></Icon>
