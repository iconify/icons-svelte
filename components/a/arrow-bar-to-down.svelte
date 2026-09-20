<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khck6er_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="khck6er_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-bar-to-down" {...props}></Icon>
