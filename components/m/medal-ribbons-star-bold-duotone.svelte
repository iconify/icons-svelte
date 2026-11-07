<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/so45uzv5f.css';
import '../../css/w/w7_a60-yr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="so45uzv5f"/><path clip-rule="evenodd" class="w7_a60-yr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:medal-ribbons-star-bold-duotone" {...props}></Icon>
