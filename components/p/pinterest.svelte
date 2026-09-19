<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmswvl73a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":344,"height":432};
const content = `<path class="hmswvl73a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:pinterest" {...props}></Icon>
