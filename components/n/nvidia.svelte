<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nis_c71-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nis_c71-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:nvidia" {...props}></Icon>
