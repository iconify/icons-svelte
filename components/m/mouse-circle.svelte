<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyu0xf38q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vyu0xf38q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:mouse-circle" {...props}></Icon>
