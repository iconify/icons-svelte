<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4ijzfbdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n4ijzfbdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:align-objects-top" {...props}></Icon>
