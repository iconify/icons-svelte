<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzx2p7ngo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mzx2p7ngo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:broom" {...props}></Icon>
