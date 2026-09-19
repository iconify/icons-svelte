<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6zk_hi4f.css';
import '../../css/k/kwb2ybc3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="t6zk_hi4f"/><path class="kwb2ybc3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:namespace-line" {...props}></Icon>
