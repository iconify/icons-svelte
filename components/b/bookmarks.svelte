<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uayhwehie.css';
import '../../css/b/bm73ro2ie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uayhwehie"/><path class="bm73ro2ie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:bookmarks" {...props}></Icon>
