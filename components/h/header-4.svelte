<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgve9iglu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-4.5,"top":-7};
const content = `<path class="vgve9iglu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:header-4" {...props}></Icon>
