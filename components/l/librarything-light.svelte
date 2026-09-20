<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tom2gdcyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tom2gdcyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:librarything-light" {...props}></Icon>
