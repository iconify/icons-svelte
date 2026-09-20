<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9_iqvdnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="p9_iqvdnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:arrow-up-to-book-with-bookmark-in-slot" {...props}></Icon>
