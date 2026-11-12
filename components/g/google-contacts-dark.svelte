<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xq5ai9bxx.css';
import '../../css/q/q2ap52b-o.css';
import '../../css/f/fipn1mb5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xq5ai9bxx"/><path class="q2ap52b-o"/><path class="fipn1mb5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:google-contacts-dark" {...props}></Icon>
