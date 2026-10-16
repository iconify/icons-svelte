<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvrtv7bqi.css';
import '../../css/p/pazdl73hk.css';
import '../../css/p/p7nvdbbgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fvrtv7bqi"/><path class="pazdl73hk"/><path class="p7nvdbbgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:refuse-truck-20-bold" {...props}></Icon>
