<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ex5i2y_lu.css';
import '../../css/k/ka-iktbmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ex5i2y_lu"/><path class="ka-iktbmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:oven-mitts-minimalistic-bold-duotone" {...props}></Icon>
