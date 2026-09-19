<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iey856b5w.css';
import '../../css/a/aelxiub-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iey856b5w"/><path class="aelxiub-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:chalkboard" {...props}></Icon>
