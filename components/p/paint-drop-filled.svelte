<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/stn-nz.css';
import '../../css/s/so-from-28.css';
import '../../css/f/fill-to-1.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="stn-nz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:paint-drop-filled" {...props}></Icon>
