<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mt8f7bcaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mt8f7bcaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:rabbit-solid" {...props}></Icon>
