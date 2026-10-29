<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1m5ykyav.css';
import '../../css/u/uylh2bc2i.css';
import '../../css/w/wuyl63pyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i1m5ykyav wm-k"/><path class="uylh2bc2i wm-a"/><path class="wm-a wuyl63pyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:bat" {...props}></Icon>
