<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxcj_78hx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qxcj_78hx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:handwheel" {...props}></Icon>
