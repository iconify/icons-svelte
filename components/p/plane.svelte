<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zh21nwb7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zh21nwb7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:plane" {...props}></Icon>
