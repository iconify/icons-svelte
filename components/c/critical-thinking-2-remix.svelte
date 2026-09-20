<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_h31qb0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j_h31qb0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:critical-thinking-2-remix" {...props}></Icon>
