<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ekcb3b0rz.css';
import '../../css/j/jfwgpxqzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ekcb3b0rz"/><path class="jfwgpxqzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:fast-food" {...props}></Icon>
