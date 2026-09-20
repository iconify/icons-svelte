<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6bi1rard.css';
import '../../css/m/m5qdqtwec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r6bi1rard"/><path class="m5qdqtwec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:oak-identity-dark" {...props}></Icon>
