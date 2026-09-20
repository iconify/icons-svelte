<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9pzv_bfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y9pzv_bfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:alarm-smoke-solid" {...props}></Icon>
