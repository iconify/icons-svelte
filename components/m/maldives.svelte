<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gv8upmbsd.css';
import '../../css/d/dv__-hbaw.css';
import '../../css/r/rkeykmpmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="gv8upmbsd"/><path class="dv__-hbaw"/><path class="rkeykmpmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:maldives" {...props}></Icon>
