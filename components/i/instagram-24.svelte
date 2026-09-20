<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p__5uxbyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p__5uxbyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:instagram-24" {...props}></Icon>
