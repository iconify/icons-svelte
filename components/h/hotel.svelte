<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbr10cbls.css';
import '../../css/p/p1s_b1bnt.css';
import '../../css/f/fumefdsvh.css';
import '../../css/w/wmpwg_b2d.css';
import '../../css/e/e7p7esbpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lbr10cbls wm-a"/><path class="p1s_b1bnt wm-a"/><path class="fumefdsvh wm-a"/><path class="wm-k wmpwg_b2d"/><path class="e7p7esbpd wm-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:hotel" {...props}></Icon>
