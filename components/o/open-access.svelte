<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/otdmk9b3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":512};
const content = `<path class="otdmk9b3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:open-access" {...props}></Icon>
