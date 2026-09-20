<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yq0u8kb-s.css';
import '../../css/x/xo6cg7b4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yq0u8kb-s"/><path class="xo6cg7b4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:lusd" {...props}></Icon>
