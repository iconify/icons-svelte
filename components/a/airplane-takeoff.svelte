<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/atkc_vbwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="atkc_vbwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:airplane-takeoff" {...props}></Icon>
