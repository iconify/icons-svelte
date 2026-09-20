<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cy1g-5rhw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cy1g-5rhw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:google-cloud-logo-solid" {...props}></Icon>
