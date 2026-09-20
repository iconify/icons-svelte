<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_e3a2unw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a_e3a2unw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ciphermail-light" {...props}></Icon>
