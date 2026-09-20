<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xu4w_7b6f.css';
import '../../css/e/eov2hibfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xu4w_7b6f"/><path class="eov2hibfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cloud-windy-fill" {...props}></Icon>
