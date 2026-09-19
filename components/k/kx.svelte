<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fs6905b6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fs6905b6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:kx" {...props}></Icon>
