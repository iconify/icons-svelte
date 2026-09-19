<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0vsl-bfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f0vsl-bfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:kotlin" {...props}></Icon>
