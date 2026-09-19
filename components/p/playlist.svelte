<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rsljz7bgq.css';
import '../../css/b/bgbj2wc5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rsljz7bgq"/><path class="bgbj2wc5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:playlist" {...props}></Icon>
