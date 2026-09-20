<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7n7j88xq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t7n7j88xq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-mercedes" {...props}></Icon>
