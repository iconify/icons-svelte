<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ah0u-xqmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ah0u-xqmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:circuit-board-solid" {...props}></Icon>
