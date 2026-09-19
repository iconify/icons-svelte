<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aadf2yd4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="aadf2yd4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:alien-monster" {...props}></Icon>
