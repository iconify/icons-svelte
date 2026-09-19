<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bx2h32bin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bx2h32bin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:framer" {...props}></Icon>
