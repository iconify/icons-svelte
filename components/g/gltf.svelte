<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/myq_jd-_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="myq_jd-_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:gltf" {...props}></Icon>
