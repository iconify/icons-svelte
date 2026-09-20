<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0y9095ca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g0y9095ca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-header-5" {...props}></Icon>
