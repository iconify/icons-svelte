<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vd8a_3tzp.css';
import '../../css/z/zv9pswjkm.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 vd8a_3tzp"/><path class="clr-i-solid clr-i-solid-path-2 zv9pswjkm"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:logout-solid" {...props}></Icon>
