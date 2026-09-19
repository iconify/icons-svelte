<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3k1-4h4j.css';
import '../../css/k/k0n5xoqvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="b3k1-4h4j"/><path class="k0n5xoqvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:new-window-fill-12" {...props}></Icon>
