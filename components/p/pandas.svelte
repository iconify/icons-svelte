<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nyl2dfb3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="nyl2dfb3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:pandas" {...props}></Icon>
