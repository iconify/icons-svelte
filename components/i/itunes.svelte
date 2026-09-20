<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfxc1rbua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vfxc1rbua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:itunes" {...props}></Icon>
