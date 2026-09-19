<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p75bl6b9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p75bl6b9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:adobe" {...props}></Icon>
