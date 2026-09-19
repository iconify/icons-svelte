<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/at2p-abdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":544,"height":512};
const content = `<path class="at2p-abdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:highlighter" {...props}></Icon>
