<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gouxmnbpb.css';
import '../../css/k/kqpq3jb5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gouxmnbpb"/><path class="kqpq3jb5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-floppy-disk" {...props}></Icon>
