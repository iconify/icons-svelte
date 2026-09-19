<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5-h-rzii.css';
import '../../css/d/d01u25bof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s5-h-rzii"/><path class="d01u25bof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:log-out" {...props}></Icon>
