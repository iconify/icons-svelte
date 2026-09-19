<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2l7g6b8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g2l7g6b8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:crop" {...props}></Icon>
