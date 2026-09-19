<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lcuv1qq0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lcuv1qq0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:latino" {...props}></Icon>
