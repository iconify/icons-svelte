<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvk04dbqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pvk04dbqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrows-move-vertical" {...props}></Icon>
