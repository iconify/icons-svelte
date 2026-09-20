<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plbpu-ttj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="plbpu-ttj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:google-fit-logo-solid" {...props}></Icon>
