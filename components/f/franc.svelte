<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d47xi2b9o.css';
import '../../css/p/pb9ghc-7p.css';
import '../../css/v/vd00roi9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d47xi2b9o"/><path class="pb9ghc-7p"/><path class="vd00roi9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:franc" {...props}></Icon>
