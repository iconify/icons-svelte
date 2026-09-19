<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jr1lh7bho.css';
import '../../css/l/ln2i4ybzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jr1lh7bho"/><path class="ln2i4ybzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:copy" {...props}></Icon>
