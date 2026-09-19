<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/donj61b_d.css';
import '../../css/b/bgbj2wc5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="donj61b_d"/><path class="bgbj2wc5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-playlist" {...props}></Icon>
