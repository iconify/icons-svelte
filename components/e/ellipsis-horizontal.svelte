<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulv-178_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ulv-178_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:ellipsis-horizontal" {...props}></Icon>
