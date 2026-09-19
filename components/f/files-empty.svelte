<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kq_lh9b1r.css';
import '../../css/z/z2r6h84kl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kq_lh9b1r"/><path class="z2r6h84kl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:files-empty" {...props}></Icon>
