<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g25gybccv.css';
import '../../css/e/egh3d5cfd.css';
import '../../css/v/vvpeo-3dh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="g25gybccv"/><path class="egh3d5cfd"/><path class="vvpeo-3dh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:house-minus-20" {...props}></Icon>
