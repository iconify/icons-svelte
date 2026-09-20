<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5-v1l30e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d5-v1l30e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:microsoft-windows-logo-1-solid" {...props}></Icon>
