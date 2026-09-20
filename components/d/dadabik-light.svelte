<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mge4dfs-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mge4dfs-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dadabik-light" {...props}></Icon>
