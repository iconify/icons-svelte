<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ml7td3-ud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ml7td3-ud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:angle-right-filled" {...props}></Icon>
