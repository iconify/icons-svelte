<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/puz4ss72c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="puz4ss72c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:pages" {...props}></Icon>
