<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgwafxbhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cgwafxbhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:roman-numeral-iv-above-water" {...props}></Icon>
