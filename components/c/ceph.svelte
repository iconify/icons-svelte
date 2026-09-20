<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxrusf8ff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vxrusf8ff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:ceph" {...props}></Icon>
