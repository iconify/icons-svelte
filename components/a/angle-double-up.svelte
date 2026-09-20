<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dq8ox75ei.css';
import '../../css/r/r3i--soji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":25};
const content = `<path class="dq8ox75ei"/><path class="r3i--soji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:angle-double-up" {...props}></Icon>
