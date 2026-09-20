<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nwwfp2bnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":25};
const content = `<path class="nwwfp2bnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:font-background-filled" {...props}></Icon>
