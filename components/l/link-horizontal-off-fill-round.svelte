<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aapds4maj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aapds4maj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:link-horizontal-off-fill-round" {...props}></Icon>
