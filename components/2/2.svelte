<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xwh29wbvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="xwh29wbvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:2" {...props}></Icon>
