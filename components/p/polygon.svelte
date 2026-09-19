<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2jwcgbdq.css';
import '../../css/c/cu9d7nszf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="f2jwcgbdq"/><path class="cu9d7nszf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:polygon" {...props}></Icon>
