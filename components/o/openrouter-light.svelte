<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lki3iqzto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lki3iqzto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:openrouter-light" {...props}></Icon>
