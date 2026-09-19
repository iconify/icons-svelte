<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gafr-ibcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":434,"height":512};
const content = `<path class="gafr-ibcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:keynote" {...props}></Icon>
