<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmvg3yb7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hmvg3yb7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:box3-filled" {...props}></Icon>
