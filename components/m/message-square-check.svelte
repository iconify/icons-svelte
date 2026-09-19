<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yk4qf0b7g.css';
import '../../css/r/rk3gvtbfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yk4qf0b7g"/><path class="rk3gvtbfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:message-square-check" {...props}></Icon>
