<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfpztpwdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xfpztpwdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:potted-plant-fill-round" {...props}></Icon>
