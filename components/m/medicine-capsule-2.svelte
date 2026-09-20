<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxf93rbng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mxf93rbng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:medicine-capsule-2" {...props}></Icon>
