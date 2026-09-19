<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wrac4jb6o.css';
import '../../css/l/lbx2im02e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wrac4jb6o"/><path class="lbx2im02e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:edit-outline" {...props}></Icon>
