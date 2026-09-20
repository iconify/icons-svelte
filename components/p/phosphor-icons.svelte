<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3vz5ekve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i3vz5ekve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:phosphor-icons" {...props}></Icon>
