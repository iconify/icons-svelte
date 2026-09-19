<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwl_1uwuq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gwl_1uwuq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:arrow-down-05" {...props}></Icon>
