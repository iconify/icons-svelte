<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrlsc76an.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zrlsc76an"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-move-down-x" {...props}></Icon>
