<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9hnrnnmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="b9hnrnnmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:propane-tank-with-gas-flame" {...props}></Icon>
