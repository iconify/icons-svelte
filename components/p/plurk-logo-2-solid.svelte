<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vu5wtw1zf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vu5wtw1zf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:plurk-logo-2-solid" {...props}></Icon>
