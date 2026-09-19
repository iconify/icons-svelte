<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ntm3w5bsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ntm3w5bsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:crossmark" {...props}></Icon>
