<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvh8u_b-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gvh8u_b-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:heart2-filled" {...props}></Icon>
