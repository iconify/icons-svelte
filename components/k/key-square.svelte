<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/snxmfpgdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="snxmfpgdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:key-square" {...props}></Icon>
