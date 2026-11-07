<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bw53xhb4q.css';
import '../../css/s/s0u7hix8w.css';
import '../../css/r/rg3j4qb_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bw53xhb4q"/><path class="s0u7hix8w"/><path class="rg3j4qb_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cart-large-bold" {...props}></Icon>
