<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ey9xu1u9w.css';
import '../../css/z/zn204jbmn.css';
import '../../css/f/f01zc3pzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ey9xu1u9w"/><path class="zn204jbmn"/><path clip-rule="evenodd" class="f01zc3pzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:git-graph-outline" {...props}></Icon>
