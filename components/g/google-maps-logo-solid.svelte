<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ar8r-icbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ar8r-icbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:google-maps-logo-solid" {...props}></Icon>
