<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fs6tz1b4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fs6tz1b4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:arrow-left2" {...props}></Icon>
