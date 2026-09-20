<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlyowj34g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zlyowj34g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:flag-solid" {...props}></Icon>
