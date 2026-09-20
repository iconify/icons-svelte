<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_qxrtbpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s_qxrtbpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:discord" {...props}></Icon>
