<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/b_9rv5rhc.css';
import '../../css/w/w4w65tb6p.css';
import '../../css/l/ld3t4ab-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="b_9rv5rhc"/><path class="w4w65tb6p"/><path class="ld3t4ab-p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:file-unlocked" {...props}></Icon>
