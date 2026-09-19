<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iud89e5vo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iud89e5vo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:insert-bottom-image" {...props}></Icon>
