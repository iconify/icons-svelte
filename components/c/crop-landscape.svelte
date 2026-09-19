<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w13w75bur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="w13w75bur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:crop-landscape" {...props}></Icon>
