<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_an92bjh.css';
import '../../css/a/aj2v-hbjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x_an92bjh"/><path class="aj2v-hbjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:carcare" {...props}></Icon>
