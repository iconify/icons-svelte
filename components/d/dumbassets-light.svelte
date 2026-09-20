<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pppxsgp7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pppxsgp7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dumbassets-light" {...props}></Icon>
