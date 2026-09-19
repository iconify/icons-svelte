<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xop-2uvkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xop-2uvkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cup-tea" {...props}></Icon>
