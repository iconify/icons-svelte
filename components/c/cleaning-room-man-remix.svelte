<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfnvn2bvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zfnvn2bvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:cleaning-room-man-remix" {...props}></Icon>
