<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rn9uzzb_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rn9uzzb_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:hearing-deaf-1-remix" {...props}></Icon>
