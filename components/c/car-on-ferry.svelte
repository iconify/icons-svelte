<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wrlxi170y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wrlxi170y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:car-on-ferry" {...props}></Icon>
