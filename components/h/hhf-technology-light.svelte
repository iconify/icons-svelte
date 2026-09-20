<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-uwexb4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u-uwexb4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hhf-technology-light" {...props}></Icon>
