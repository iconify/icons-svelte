<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxkbl7sqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dxkbl7sqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:cainiao" {...props}></Icon>
