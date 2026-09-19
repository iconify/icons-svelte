<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmu8-9b0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="gmu8-9b0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:file-image" {...props}></Icon>
