<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kofyy-e0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kofyy-e0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:heart-angle-outline" {...props}></Icon>
