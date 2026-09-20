<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfcf6nbxf.css';
import '../../css/x/x0bdrkbiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rfcf6nbxf"/><path clip-rule="evenodd" class="x0bdrkbiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:drive-32" {...props}></Icon>
