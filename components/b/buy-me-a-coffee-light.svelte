<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjum9-bhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sjum9-bhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:buy-me-a-coffee-light" {...props}></Icon>
