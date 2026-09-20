<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1rk6ccif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n1rk6ccif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:amicoscript-dark" {...props}></Icon>
