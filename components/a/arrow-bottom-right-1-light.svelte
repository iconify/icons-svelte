<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0gcthm3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x0gcthm3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-bottom-right-1-light" {...props}></Icon>
