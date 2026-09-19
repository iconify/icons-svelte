<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-8nonb3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":356,"height":512};
const content = `<path class="r-8nonb3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:build-boot" {...props}></Icon>
