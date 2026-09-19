<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzpr2g3su.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zzpr2g3su"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:parent-and-infant-priority-seating" {...props}></Icon>
