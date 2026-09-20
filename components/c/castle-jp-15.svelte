<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xz3g_ob0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xz3g_ob0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:castle-jp-15" {...props}></Icon>
