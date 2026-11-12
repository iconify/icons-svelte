<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3j8a4h1u.css';
import '../../css/r/r3b4dgb9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l3j8a4h1u"/><path class="r3b4dgb9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:feedly" {...props}></Icon>
