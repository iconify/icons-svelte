<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t60g_5qhi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t60g_5qhi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:forgejo-dark" {...props}></Icon>
