<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l50xdjbwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l50xdjbwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:align-horizontal-space-between" {...props}></Icon>
