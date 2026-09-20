<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bl7ixn8fa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bl7ixn8fa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:opentalk" {...props}></Icon>
