<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mo709nj-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":16};
const content = `<path class="mo709nj-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:lock" {...props}></Icon>
