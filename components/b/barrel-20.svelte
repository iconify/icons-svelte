<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xs4nodbts.css';
import '../../css/g/gy2cg1ook.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xs4nodbts"/><path class="gy2cg1ook"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:barrel-20" {...props}></Icon>
