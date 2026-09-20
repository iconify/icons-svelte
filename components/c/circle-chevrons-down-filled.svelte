<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ret1j0k_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ret1j0k_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-chevrons-down-filled" {...props}></Icon>
