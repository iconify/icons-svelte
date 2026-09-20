<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmm6kfbbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lmm6kfbbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:box-3d-fill" {...props}></Icon>
