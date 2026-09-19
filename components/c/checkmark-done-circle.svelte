<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-hd3s68u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a-hd3s68u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:checkmark-done-circle" {...props}></Icon>
