<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/seq8pl07q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="seq8pl07q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:pathfinder-outline-remix" {...props}></Icon>
