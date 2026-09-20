<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e4u0swhdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e4u0swhdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:krakend-light" {...props}></Icon>
