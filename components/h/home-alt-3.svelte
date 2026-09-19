<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/br-uotb6n.css';
import '../../css/l/lw6k7rbph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="br-uotb6n"/><path class="lw6k7rbph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:home-alt-3" {...props}></Icon>
