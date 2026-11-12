<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9jb50raj.css';
import '../../css/x/x23q6jtbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r9jb50raj"/><path class="x23q6jtbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ovumcy-light" {...props}></Icon>
