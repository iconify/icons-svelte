<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0gx-2k1c.css';
import '../../css/s/slvmq7bsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="k0gx-2k1c"/><path clip-rule="evenodd" class="slvmq7bsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pinepods-light" {...props}></Icon>
