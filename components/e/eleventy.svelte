<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jyka9_bye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="jyka9_bye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:eleventy" {...props}></Icon>
