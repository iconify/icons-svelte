<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yr9aj_vax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yr9aj_vax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:paperclip-48" {...props}></Icon>
