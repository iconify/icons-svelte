<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mnlh_2gfq.css';
import '../../css/u/uqv04wb6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mnlh_2gfq"/><path class="uqv04wb6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:crowd" {...props}></Icon>
