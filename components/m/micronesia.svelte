<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rpfjsd0jn.css';
import '../../css/i/iqumv76zj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="rpfjsd0jn"/><path class="iqumv76zj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:micronesia" {...props}></Icon>
