<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hy84wsa-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hy84wsa-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:google-hangouts" {...props}></Icon>
