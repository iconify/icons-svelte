<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-ykpjboh.css';
import '../../css/w/w-yr_fb2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="j-ykpjboh"/><path class="w-yr_fb2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ethernet-port-48-bold" {...props}></Icon>
