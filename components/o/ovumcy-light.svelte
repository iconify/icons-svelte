<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9jb50raj.css';
import '../../css/j/jzvh2fb3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r9jb50raj"/><path class="jzvh2fb3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ovumcy-light" {...props}></Icon>
