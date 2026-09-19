<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gi8h8gaxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gi8h8gaxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:powershell" {...props}></Icon>
