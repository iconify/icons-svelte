<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lee2lacrz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lee2lacrz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dailytxt-light" {...props}></Icon>
