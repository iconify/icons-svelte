<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b25a24pbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b25a24pbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:prowlarr-light" {...props}></Icon>
