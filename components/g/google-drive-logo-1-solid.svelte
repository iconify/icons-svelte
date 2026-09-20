<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbzda_bdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vbzda_bdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:google-drive-logo-1-solid" {...props}></Icon>
