<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mte30snjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mte30snjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:flux" {...props}></Icon>
