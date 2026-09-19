<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxv6y6bpx.css';
import '../../css/k/kdqyt0wqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mxv6y6bpx"/><path class="kdqyt0wqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:headphone-alt-2-filled" {...props}></Icon>
