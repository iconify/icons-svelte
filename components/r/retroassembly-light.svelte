<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pbrl8dbjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pbrl8dbjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:retroassembly-light" {...props}></Icon>
