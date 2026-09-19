<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ey03wibpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ey03wibpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:hospital-circle-solid" {...props}></Icon>
