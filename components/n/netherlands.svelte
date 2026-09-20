<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-vv3dbhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="p-vv3dbhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:netherlands" {...props}></Icon>
