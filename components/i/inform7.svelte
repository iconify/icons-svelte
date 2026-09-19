<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksz2pjk8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ksz2pjk8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:inform7" {...props}></Icon>
