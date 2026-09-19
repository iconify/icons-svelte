<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ssv2w4v0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":750,"height":850};
const content = `<path class="ssv2w4v0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:conversation" {...props}></Icon>
