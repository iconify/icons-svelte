<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idqiyb76f.css';
import '../../css/h/hwema026b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="idqiyb76f"/><path clip-rule="evenodd" class="hwema026b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:mushroom-5" {...props}></Icon>
