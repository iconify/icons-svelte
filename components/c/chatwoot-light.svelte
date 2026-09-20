<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gs3w2zbwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gs3w2zbwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:chatwoot-light" {...props}></Icon>
