<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxc1niezf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bxc1niezf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:chess-king" {...props}></Icon>
