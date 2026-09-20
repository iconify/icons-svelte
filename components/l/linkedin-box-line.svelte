<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bpno3-vgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bpno3-vgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:linkedin-box-line" {...props}></Icon>
