<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yiwzlsbsz.css';
import '../../css/z/zz89phbve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yiwzlsbsz"/><path class="zz89phbve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:mail-warning-filled" {...props}></Icon>
