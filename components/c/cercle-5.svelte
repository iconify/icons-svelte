<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i01g5y-bj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i01g5y-bj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:cercle-5" {...props}></Icon>
