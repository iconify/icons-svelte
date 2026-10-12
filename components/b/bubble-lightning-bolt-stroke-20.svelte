<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-7j0sgsx.css';
import '../../css/b/bmmy7ztjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="a-7j0sgsx"/><path class="bmmy7ztjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:bubble-lightning-bolt-stroke-20" {...props}></Icon>
