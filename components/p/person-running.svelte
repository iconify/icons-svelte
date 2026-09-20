<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lu60hnbbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lu60hnbbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-running" {...props}></Icon>
