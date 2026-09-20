<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_q8qubpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r_q8qubpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:mushroom-filled" {...props}></Icon>
