<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxzkk6bvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mxzkk6bvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:camera-solid" {...props}></Icon>
