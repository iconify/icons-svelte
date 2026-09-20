<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/znde4_osf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="znde4_osf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:badge" {...props}></Icon>
