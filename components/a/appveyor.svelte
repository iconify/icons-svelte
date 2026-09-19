<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shr4fu72y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="shr4fu72y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:appveyor" {...props}></Icon>
