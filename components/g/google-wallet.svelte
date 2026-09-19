<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzz_8cbhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xzz_8cbhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:google-wallet" {...props}></Icon>
