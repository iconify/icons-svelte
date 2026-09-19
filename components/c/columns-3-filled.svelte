<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6nt_usom.css';
import '../../css/l/lfbnv8wtq.css';
import '../../css/b/bh5vgerfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="e6nt_usom"/><rect class="lfbnv8wtq"/><rect class="bh5vgerfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:columns-3-filled" {...props}></Icon>
