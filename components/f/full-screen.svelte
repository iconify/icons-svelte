<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sye3enc-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sye3enc-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:full-screen" {...props}></Icon>
