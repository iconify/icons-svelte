<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m76uv7b2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m76uv7b2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:bridge-5-filled" {...props}></Icon>
