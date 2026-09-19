<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ix-de3bgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="ix-de3bgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:fly" {...props}></Icon>
