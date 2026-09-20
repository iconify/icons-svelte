<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xro_uz.css';
import '../../css/d/d-xntmfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xro_uz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:menu-to-close-transition" {...props}></Icon>
