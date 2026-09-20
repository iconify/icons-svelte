<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ux88xgv7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ux88xgv7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:jackett-dark" {...props}></Icon>
