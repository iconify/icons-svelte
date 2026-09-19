<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afuem_b_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="afuem_b_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:roomsstaircase" {...props}></Icon>
