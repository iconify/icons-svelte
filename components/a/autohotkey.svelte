<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rsa1xl24d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rsa1xl24d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:autohotkey" {...props}></Icon>
