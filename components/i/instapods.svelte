<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xp7g_-gpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xp7g_-gpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:instapods" {...props}></Icon>
