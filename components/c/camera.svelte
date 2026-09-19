<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/va7_sv_vn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="va7_sv_vn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:camera" {...props}></Icon>
