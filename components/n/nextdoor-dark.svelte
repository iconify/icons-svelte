<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9_q-5ksh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z9_q-5ksh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nextdoor-dark" {...props}></Icon>
