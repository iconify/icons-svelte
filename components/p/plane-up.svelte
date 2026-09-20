<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhhhj_z0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="vhhhj_z0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:plane-up" {...props}></Icon>
