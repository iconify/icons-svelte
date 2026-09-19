<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/br5j05_gi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="br5j05_gi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:drizzle-orm" {...props}></Icon>
