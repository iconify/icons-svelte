<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bj84wmbsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bj84wmbsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:olivetin-dark" {...props}></Icon>
