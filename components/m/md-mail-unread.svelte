<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lz7g-qohu.css';
import '../../css/x/xafs55bpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="lz7g-qohu"/><path class="xafs55bpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-mail-unread" {...props}></Icon>
