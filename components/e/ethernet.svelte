<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psz3s1eih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="psz3s1eih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:ethernet" {...props}></Icon>
