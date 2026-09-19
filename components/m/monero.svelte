<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/galr4-yxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="galr4-yxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:monero" {...props}></Icon>
