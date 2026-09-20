<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ltz0s7b4l.css';
import '../../css/x/x15y2eb4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ltz0s7b4l"/><path class="x15y2eb4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:jst" {...props}></Icon>
