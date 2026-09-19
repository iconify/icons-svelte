<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1j59_5rt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l1j59_5rt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:blacklargesquare" {...props}></Icon>
