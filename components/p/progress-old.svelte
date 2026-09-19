<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yre9_ib2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yre9_ib2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:progress-old" {...props}></Icon>
