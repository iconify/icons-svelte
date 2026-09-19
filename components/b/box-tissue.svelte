<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r1fimrb1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r1fimrb1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:box-tissue" {...props}></Icon>
