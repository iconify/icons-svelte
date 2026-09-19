<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kk66pobvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kk66pobvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-left-stroke-circle-filled" {...props}></Icon>
