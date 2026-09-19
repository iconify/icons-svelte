<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nm99wgorg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nm99wgorg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:intel" {...props}></Icon>
