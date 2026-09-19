<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glon_br_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="glon_br_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:open-vpn" {...props}></Icon>
