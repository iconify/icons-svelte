<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4ioyfbzk.css';
import '../../css/h/hie35vbnj.css';
import '../../css/k/k1t7ff4oh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b4ioyfbzk wm-k"/><path class="hie35vbnj wm-k"/><path class="k1t7ff4oh wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:dog" {...props}></Icon>
