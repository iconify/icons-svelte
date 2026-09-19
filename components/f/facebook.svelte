<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6j1x8b6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k6j1x8b6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:facebook" {...props}></Icon>
