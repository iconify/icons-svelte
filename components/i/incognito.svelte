<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi81glb1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="bi81glb1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:incognito" {...props}></Icon>
