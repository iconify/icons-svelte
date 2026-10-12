<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bm3-8ybbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bm3-8ybbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:lock-fill-20" {...props}></Icon>
