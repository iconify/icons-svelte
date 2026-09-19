<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ty0_57byk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="ty0_57byk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:pause" {...props}></Icon>
