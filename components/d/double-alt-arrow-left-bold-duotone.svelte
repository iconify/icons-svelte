<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rb4o__b5r.css';
import '../../css/n/n2zpnybfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rb4o__b5r"/><path clip-rule="evenodd" class="n2zpnybfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:double-alt-arrow-left-bold-duotone" {...props}></Icon>
