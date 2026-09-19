<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mf6nftywu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1760,"height":1792};
const content = `<path class="mf6nftywu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:google-wallet" {...props}></Icon>
