<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a6vrhzb-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a6vrhzb-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:brush-outline" {...props}></Icon>
