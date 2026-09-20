<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpxlm7b3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lpxlm7b3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:bookhaven-light" {...props}></Icon>
