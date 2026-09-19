<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qluhj6bgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qluhj6bgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:nose-outline-24px" {...props}></Icon>
