<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3wqznb4l.css';
import '../../css/d/d4j9nrbeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e3wqznb4l"/><path class="d4j9nrbeu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:nmx" {...props}></Icon>
