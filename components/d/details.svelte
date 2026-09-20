<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qk_hy4r_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qk_hy4r_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:details" {...props}></Icon>
