<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecff8-bmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ecff8-bmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:immich-public-proxy-light" {...props}></Icon>
