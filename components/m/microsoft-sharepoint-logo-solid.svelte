<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjois9l_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rjois9l_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:microsoft-sharepoint-logo-solid" {...props}></Icon>
