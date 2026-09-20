<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bp-k0xoma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bp-k0xoma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:confluence-light" {...props}></Icon>
