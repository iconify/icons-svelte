<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sb7ms080d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="sb7ms080d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:file-cabinet" {...props}></Icon>
