<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxjh9tbuw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qxjh9tbuw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:remove-eye-filled" {...props}></Icon>
