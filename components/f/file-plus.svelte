<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wluj6wb6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wluj6wb6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:file-plus" {...props}></Icon>
