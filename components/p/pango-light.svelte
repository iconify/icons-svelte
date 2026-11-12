<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwzed5t3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pwzed5t3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pango-light" {...props}></Icon>
