<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f40r4ef-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f40r4ef-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:notification" {...props}></Icon>
