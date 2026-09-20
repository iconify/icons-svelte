<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dlkw1s6vn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dlkw1s6vn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:iconjar-logo-solid" {...props}></Icon>
