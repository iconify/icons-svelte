<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rirdx665u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="rirdx665u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:phalcon" {...props}></Icon>
