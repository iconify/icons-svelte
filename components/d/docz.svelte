<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uamfscbae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":511.999,"height":511.999};
const content = `<path class="uamfscbae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:docz" {...props}></Icon>
