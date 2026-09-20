<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uz_dv7bxn.css';
import '../../css/a/aikx1pj2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uz_dv7bxn"/><path class="aikx1pj2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:book-heart" {...props}></Icon>
