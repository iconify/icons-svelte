<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r1xv0ntbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r1xv0ntbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:orcah-studio-dark" {...props}></Icon>
