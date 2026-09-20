<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3ke_fu8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="m3ke_fu8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:folder-tick-outline" {...props}></Icon>
