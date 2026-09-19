<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6zjh8b-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="c6zjh8b-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:helix" {...props}></Icon>
