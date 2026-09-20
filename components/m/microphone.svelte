<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ary8e2ekk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ary8e2ekk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:microphone" {...props}></Icon>
