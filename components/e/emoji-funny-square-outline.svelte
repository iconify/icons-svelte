<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4xa_-g-t.css';
import '../../css/x/x1ss0rbtf.css';
import '../../css/m/mwvc4bkeq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d4xa_-g-t"/><path class="x1ss0rbtf"/><path clip-rule="evenodd" class="mwvc4bkeq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:emoji-funny-square-outline" {...props}></Icon>
