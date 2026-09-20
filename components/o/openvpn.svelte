<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i854e3-ii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i854e3-ii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:openvpn" {...props}></Icon>
