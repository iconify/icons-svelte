<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bp4k5yfan.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bp4k5yfan"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:apple-fill-round" {...props}></Icon>
