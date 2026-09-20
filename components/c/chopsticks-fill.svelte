<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bptbgsbhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bptbgsbhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chopsticks-fill" {...props}></Icon>
