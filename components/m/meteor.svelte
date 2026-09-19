<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6tlncb-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="f6tlncb-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:meteor" {...props}></Icon>
