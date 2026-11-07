<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqbs--b0w.css';
import '../../css/b/bgpl6nb6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yqbs--b0w"/><path clip-rule="evenodd" class="bgpl6nb6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:remote-controller-bold" {...props}></Icon>
