<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsyd9_bju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lsyd9_bju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:menu-alt3" {...props}></Icon>
