<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ae8qgnbhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ae8qgnbhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:logo-vimeo" {...props}></Icon>
