<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7w8ann-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":480,"height":512};
const content = `<path class="n7w8ann-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:earlybirds" {...props}></Icon>
