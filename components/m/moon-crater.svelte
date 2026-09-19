<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/js7tbtbkw.css';
import '../../css/j/j1nyzswop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="js7tbtbkw"/><path class="j1nyzswop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:moon-crater" {...props}></Icon>
