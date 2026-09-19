<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pv05icc_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pv05icc_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:fire-extinguisher-filled" {...props}></Icon>
