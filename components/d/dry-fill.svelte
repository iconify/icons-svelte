<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4_xldbbg.css';
import '../../css/z/zlbz5jbgm.css';
import '../../css/z/zhg6ptbsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b4_xldbbg"/><path clip-rule="evenodd" class="zlbz5jbgm"/><path clip-rule="evenodd" class="zhg6ptbsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:dry-fill" {...props}></Icon>
