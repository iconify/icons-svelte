<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpzz9abup.css';
import '../../css/z/znd-kf3wq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lpzz9abup"/><path class="znd-kf3wq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:controls-slider-toggle-left" {...props}></Icon>
