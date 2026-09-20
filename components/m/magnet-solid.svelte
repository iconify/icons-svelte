<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxn3t907l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dxn3t907l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:magnet-solid" {...props}></Icon>
