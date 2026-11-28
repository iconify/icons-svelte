<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iu00t77rk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="iu00t77rk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:passport-bold" {...props}></Icon>
