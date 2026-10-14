<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lv2r58bup.css';
import '../../css/k/k0khjcc8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lv2r58bup"/><path class="k0khjcc8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:code-badge-16" {...props}></Icon>
