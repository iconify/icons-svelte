<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tl5jgnb6c.css';
import '../../css/z/zdmdccc7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="tl5jgnb6c"/><path class="zdmdccc7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:child" {...props}></Icon>
