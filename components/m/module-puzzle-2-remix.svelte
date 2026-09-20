<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b10v80bpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b10v80bpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:module-puzzle-2-remix" {...props}></Icon>
