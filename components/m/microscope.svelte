<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/asv9wshbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="asv9wshbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:microscope" {...props}></Icon>
