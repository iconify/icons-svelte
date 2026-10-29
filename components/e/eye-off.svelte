<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3gm-abug.css';
import '../../css/g/gxgk1_b8t.css';
import '../../css/m/mbzw4qy1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v3gm-abug wm-k"/><path class="gxgk1_b8t wm-s"/><path class="mbzw4qy1w wm-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:eye-off" {...props}></Icon>
