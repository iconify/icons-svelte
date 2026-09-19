<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tutwf7z4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tutwf7z4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-infinite" {...props}></Icon>
