<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vpouiobrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="vpouiobrc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:collection-music" {...props}></Icon>
