<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/stss5vbih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":491,"height":512};
const content = `<path class="stss5vbih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:awk" {...props}></Icon>
