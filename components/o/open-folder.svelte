<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bgl6b1yyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bgl6b1yyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:open-folder" {...props}></Icon>
