<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bm42pmb9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bm42pmb9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:anilist" {...props}></Icon>
