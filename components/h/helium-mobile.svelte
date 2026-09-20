<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-nq5eyhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j-nq5eyhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:helium-mobile" {...props}></Icon>
