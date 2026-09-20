<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a78208mbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a78208mbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:connector-rect" {...props}></Icon>
