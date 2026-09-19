<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/coapld2vp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="coapld2vp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:folder" {...props}></Icon>
