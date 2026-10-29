<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utqzt6bcp.css';
import '../../css/b/bymhq5bkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="utqzt6bcp wm-k"/><path class="bymhq5bkw wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:meh" {...props}></Icon>
