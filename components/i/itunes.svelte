<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fe702wb9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":488};
const content = `<path class="fe702wb9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:itunes" {...props}></Icon>
