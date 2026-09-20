<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_z-5jb3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l_z-5jb3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:periodic-table" {...props}></Icon>
