<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxdlb5s3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oxdlb5s3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:1c" {...props}></Icon>
