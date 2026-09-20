<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grs2zwbox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="grs2zwbox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:document" {...props}></Icon>
