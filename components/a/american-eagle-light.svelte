<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cck1czbfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cck1czbfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:american-eagle-light" {...props}></Icon>
