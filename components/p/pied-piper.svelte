<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvifkjfwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2304,"height":1664};
const content = `<path class="uvifkjfwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:pied-piper" {...props}></Icon>
