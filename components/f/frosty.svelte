<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wt-1lebpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="wt-1lebpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:frosty" {...props}></Icon>
