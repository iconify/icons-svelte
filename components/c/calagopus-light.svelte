<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvwgg2gcm.css';
import '../../css/n/n9dovwblw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bvwgg2gcm"/><path class="n9dovwblw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:calagopus-light" {...props}></Icon>
