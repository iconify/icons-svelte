<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_0lc8gzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s_0lc8gzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:magicmirror2-dark" {...props}></Icon>
