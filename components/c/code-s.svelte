<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bm5xiid0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="bm5xiid0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:code-s" {...props}></Icon>
