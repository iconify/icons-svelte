<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oz4rxo_yp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oz4rxo_yp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:box-minimalistic-outline" {...props}></Icon>
