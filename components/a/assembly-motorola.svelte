<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhqq6-j_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uhqq6-j_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:assembly-motorola" {...props}></Icon>
