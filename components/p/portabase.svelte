<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bss5wybgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bss5wybgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:portabase" {...props}></Icon>
