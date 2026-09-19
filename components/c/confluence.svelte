<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8xu67bmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x8xu67bmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:confluence" {...props}></Icon>
