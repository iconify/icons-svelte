<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zt9rs6yuk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zt9rs6yuk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:file-9" {...props}></Icon>
