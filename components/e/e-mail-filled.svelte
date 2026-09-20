<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dk-bu9-no.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="dk-bu9-no"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:e-mail-filled" {...props}></Icon>
