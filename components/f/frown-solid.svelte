<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vr95qbbbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vr95qbbbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:frown-solid" {...props}></Icon>
