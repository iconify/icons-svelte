<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzq3d7bos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xzq3d7bos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:aegisauthenticator" {...props}></Icon>
