<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ktmk6lb-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ktmk6lb-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:font-awesome" {...props}></Icon>
